<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r-5hcsb2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="r-5hcsb2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:arrow-uturn-up-left-16-solid" {...props}></Icon>
