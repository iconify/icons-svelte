<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/elhco4bft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="elhco4bft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:cash-fill" {...props}></Icon>
