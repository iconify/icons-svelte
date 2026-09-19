<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/t/tbsoarh-e.css';
import '../../css/m/md286fbip.css';
import '../../css/k/k3d60aclh.css';
import '../../css/b/b6t7n-yss.css';
import '../../css/j/jdilsabed.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><circle class="tbsoarh-e"/><g class="md286fbip"><path class="k3d60aclh"/><path class="b6t7n-yss"/><path class="jdilsabed"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency-color:1inch" {...props}></Icon>
