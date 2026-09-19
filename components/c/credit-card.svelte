<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bbqm40wsr.css';
import '../../css/x/xgj3z1bgb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bbqm40wsr"/><path class="xgj3z1bgb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:credit-card" {...props}></Icon>
