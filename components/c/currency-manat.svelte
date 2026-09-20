<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/usjkl6wdf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="usjkl6wdf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:currency-manat" {...props}></Icon>
