<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ts501wnao.css';
import '../../css/m/ma0bxjbgr.css';
import '../../css/m/mxvrl8fhx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ts501wnao"/><path class="ma0bxjbgr"/><path class="mxvrl8fhx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:package-20" {...props}></Icon>
