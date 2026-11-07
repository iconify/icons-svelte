<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rdcb-2svx.css';
import '../../css/d/dod872beq.css';
import '../../css/g/g15r-phwb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rdcb-2svx"/><path class="dod872beq"/><path clip-rule="evenodd" class="g15r-phwb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bed-bold" {...props}></Icon>
