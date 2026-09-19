<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q5pnlxb7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q5pnlxb7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:flame-filled" {...props}></Icon>
