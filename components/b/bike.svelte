<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yhr8d1buy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yhr8d1buy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:bike" {...props}></Icon>
