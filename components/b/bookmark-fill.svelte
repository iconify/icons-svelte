<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dnzwelbhi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dnzwelbhi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:bookmark-fill" {...props}></Icon>
