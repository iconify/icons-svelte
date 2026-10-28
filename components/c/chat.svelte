<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f66e28mtw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f66e28mtw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codex:chat" {...props}></Icon>
