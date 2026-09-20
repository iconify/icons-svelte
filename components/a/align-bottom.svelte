<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/l/l400bnd5u.css';
import '../../css/r/rj5v1bbrm.css';
import '../../css/y/yvwyapbau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="l400bnd5u"/><rect transform="matrix(-1 0 0 1 19.75 7.75)" class="rj5v1bbrm"/><rect transform="matrix(-1 0 0 1 10.25 2.75)" class="yvwyapbau"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:align-bottom" {...props}></Icon>
