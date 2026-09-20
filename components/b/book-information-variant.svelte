<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ox73mjaja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ox73mjaja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:book-information-variant" {...props}></Icon>
