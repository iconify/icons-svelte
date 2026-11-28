<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iafu0tbcu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iafu0tbcu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:nfc" {...props}></Icon>
