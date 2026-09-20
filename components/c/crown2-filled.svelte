<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iwx53sbxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iwx53sbxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:crown2-filled" {...props}></Icon>
