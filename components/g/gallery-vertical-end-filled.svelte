<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g9nwk9bcv.css';
import '../../css/u/u42idu8ag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<rect class="g9nwk9bcv"/><path class="u42idu8ag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:gallery-vertical-end-filled" {...props}></Icon>
