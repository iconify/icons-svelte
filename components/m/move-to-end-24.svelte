<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sue7ftw_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sue7ftw_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:move-to-end-24" {...props}></Icon>
