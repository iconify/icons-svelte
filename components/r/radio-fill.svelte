<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i6c0x_jlb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i6c0x_jlb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:radio-fill" {...props}></Icon>
