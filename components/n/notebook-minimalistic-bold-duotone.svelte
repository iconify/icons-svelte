<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n5rfkzb2n.css';
import '../../css/x/xp2l2gs6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n5rfkzb2n"/><path class="xp2l2gs6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:notebook-minimalistic-bold-duotone" {...props}></Icon>
