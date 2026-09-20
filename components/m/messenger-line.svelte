<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w8s526brq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w8s526brq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:messenger-line" {...props}></Icon>
