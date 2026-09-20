<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ohcpt2bmp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ohcpt2bmp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:rotate-left" {...props}></Icon>
