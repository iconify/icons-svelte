<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cw6zjlbtb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cw6zjlbtb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:jeedom-dark" {...props}></Icon>
