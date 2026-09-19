<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v62_-3b9x.css';
import '../../css/n/nwfaqcbac.css';
import '../../css/e/ez0pggbas.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v62_-3b9x"/><path class="nwfaqcbac"/><path class="ez0pggbas"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-bullseye" {...props}></Icon>
