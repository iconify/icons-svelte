<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jtcz_kb4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jtcz_kb4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:book-text" {...props}></Icon>
