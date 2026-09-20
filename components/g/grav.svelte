<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0ulh_r9o.css';
import '../../css/f/f_rwg-r9r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="a0ulh_r9o"/><path class="f_rwg-r9r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:grav" {...props}></Icon>
