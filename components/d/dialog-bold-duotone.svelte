<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y2bl_ob4g.css';
import '../../css/m/m0pn6bzto.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y2bl_ob4g"/><path class="m0pn6bzto"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:dialog-bold-duotone" {...props}></Icon>
