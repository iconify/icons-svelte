<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oojdedcup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oojdedcup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:projector-screen-line" {...props}></Icon>
