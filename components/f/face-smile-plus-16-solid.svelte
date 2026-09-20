<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nm1ss5uze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="nm1ss5uze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:face-smile-plus-16-solid" {...props}></Icon>
