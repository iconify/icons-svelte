<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ls_ypjbmg.css';
import '../../css/u/ucj4b1l1e.css';
import '../../css/g/g4v7ni7qx.css';
import '../../css/r/rqa_vtz4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ls_ypjbmg"/><circle class="ucj4b1l1e"/><path class="g4v7ni7qx"/><path class="rqa_vtz4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:cloudreve-dark" {...props}></Icon>
