<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o_cut2bia.css';
import '../../css/v/vyoe27bvu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="o_cut2bia"/><path class="vyoe27bvu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:north-pole-security" {...props}></Icon>
