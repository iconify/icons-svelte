<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ue2-q7bvs.css';
import '../../css/k/ksp8umbhc.css';
import '../../css/s/s8tc8qojs.css';
import '../../css/c/caa41bcyj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ue2-q7bvs"/><path class="ksp8umbhc"/><path class="s8tc8qojs"/><path class="caa41bcyj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:microphone-bold-duotone" {...props}></Icon>
