<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxgx6xbbq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fxgx6xbbq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:praying-room" {...props}></Icon>
