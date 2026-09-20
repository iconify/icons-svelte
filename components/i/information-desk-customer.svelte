<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pzk-evtbl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pzk-evtbl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:information-desk-customer" {...props}></Icon>
