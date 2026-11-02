<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b1jg25bhx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b1jg25bhx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:game-2-line" {...props}></Icon>
