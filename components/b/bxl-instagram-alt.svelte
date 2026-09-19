<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l9tqfebse.css';
import '../../css/m/m7aw91b8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l9tqfebse"/><circle class="m7aw91b8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxl-instagram-alt" {...props}></Icon>
