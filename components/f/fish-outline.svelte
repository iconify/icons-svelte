<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/di3p_6bnk.css';
import '../../css/t/t8wo_rv6h.css';
import '../../css/v/vkmkxtqch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="di3p_6bnk"/><circle class="t8wo_rv6h"/><path class="vkmkxtqch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:fish-outline" {...props}></Icon>
