<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-69cibvi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i-69cibvi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:hat-and-glasses-filled" {...props}></Icon>
