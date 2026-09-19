<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ze2v6yb1y.css';
import '../../css/s/sh_nibbxh.css';
import '../../css/t/tznu3_bdm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="ze2v6yb1y"/><circle class="sh_nibbxh"/><path class="tznu3_bdm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:recording-outline" {...props}></Icon>
