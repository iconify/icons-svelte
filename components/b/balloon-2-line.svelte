<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u3jgqmb2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u3jgqmb2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:balloon-2-line" {...props}></Icon>
