<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q4gs1mbct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q4gs1mbct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:clipboard-filled-line" {...props}></Icon>
