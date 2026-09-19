<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i0vlgacxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i0vlgacxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:quote-single-left-filled" {...props}></Icon>
