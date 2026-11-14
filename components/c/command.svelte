<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vtkcz9-4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vtkcz9-4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codex:command" {...props}></Icon>
