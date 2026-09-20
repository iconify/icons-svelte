<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ffsaow-0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ffsaow-0f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:dots-horizontal" {...props}></Icon>
