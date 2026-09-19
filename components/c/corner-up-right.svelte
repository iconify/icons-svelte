<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yit344byv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yit344byv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:corner-up-right" {...props}></Icon>
