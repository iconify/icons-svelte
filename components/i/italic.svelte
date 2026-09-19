<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mp6qv9b2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mp6qv9b2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codex:italic" {...props}></Icon>
