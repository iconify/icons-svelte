<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z04v279_g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z04v279_g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:blanket" {...props}></Icon>
