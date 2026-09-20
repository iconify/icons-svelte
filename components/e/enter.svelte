<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l876m5b_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l876m5b_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:enter" {...props}></Icon>
