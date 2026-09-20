<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zxw07xz2z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zxw07xz2z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bottle-fill" {...props}></Icon>
