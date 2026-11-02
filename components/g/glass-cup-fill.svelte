<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3lzm8ber.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z3lzm8ber"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:glass-cup-fill" {...props}></Icon>
