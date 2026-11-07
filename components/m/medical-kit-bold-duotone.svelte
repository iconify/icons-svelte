<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vd4e4juil.css';
import '../../css/w/w453hdcek.css';
import '../../css/x/xsk4cbckr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vd4e4juil"/><path class="w453hdcek"/><path clip-rule="evenodd" class="xsk4cbckr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:medical-kit-bold-duotone" {...props}></Icon>
