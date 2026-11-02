<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fivs59bbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fivs59bbz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:auto-hold-fill" {...props}></Icon>
