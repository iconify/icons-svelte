<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mm52svw0n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mm52svw0n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:code-block-parentheses" {...props}></Icon>
