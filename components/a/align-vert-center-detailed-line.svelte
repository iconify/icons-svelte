<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r3chf1bcg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r3chf1bcg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:align-vert-center-detailed-line" {...props}></Icon>
