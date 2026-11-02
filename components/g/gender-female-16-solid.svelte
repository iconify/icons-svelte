<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/weuip4crh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="weuip4crh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:gender-female-16-solid" {...props}></Icon>
