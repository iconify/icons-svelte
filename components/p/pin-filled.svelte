<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fgc0kgdcw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fgc0kgdcw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:pin-filled" {...props}></Icon>
