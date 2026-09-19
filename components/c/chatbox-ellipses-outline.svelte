<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-ygl7brj.css';
import '../../css/d/dc-p_7bld.css';
import '../../css/i/iehx50jjq.css';
import '../../css/h/hnm18mbpu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l-ygl7brj"/><circle class="dc-p_7bld"/><circle class="iehx50jjq"/><circle class="hnm18mbpu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:chatbox-ellipses-outline" {...props}></Icon>
