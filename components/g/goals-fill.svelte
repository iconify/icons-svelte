<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yp-b7wzwg.css';
import '../../css/w/wsg3jcbeq.css';
import '../../css/f/f430c2b9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yp-b7wzwg"/><path class="wsg3jcbeq"/><path class="f430c2b9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:goals-fill" {...props}></Icon>
