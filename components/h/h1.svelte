<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ca7fx22mt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ca7fx22mt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codex:h1" {...props}></Icon>
