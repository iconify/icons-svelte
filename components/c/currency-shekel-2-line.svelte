<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bss2tqi7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bss2tqi7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:currency-shekel-2-line" {...props}></Icon>
