<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lc25svfcp.css';
import '../../css/j/jly7v7-2j.css';
import '../../css/f/f_km3v9ni.css';
import '../../css/a/afby5gqzh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lc25svfcp"/><path class="jly7v7-2j"/><path class="f_km3v9ni"/><path class="afby5gqzh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:maybe" {...props}></Icon>
