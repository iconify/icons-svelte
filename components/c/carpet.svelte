<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zhhj82nbe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zhhj82nbe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:carpet" {...props}></Icon>
