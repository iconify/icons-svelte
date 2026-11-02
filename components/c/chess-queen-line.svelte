<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a4e5mqb5k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a4e5mqb5k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chess-queen-line" {...props}></Icon>
