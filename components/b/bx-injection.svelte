<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zx6yh-vht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zx6yh-vht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-injection" {...props}></Icon>
