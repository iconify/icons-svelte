<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bbi20vb9l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bbi20vb9l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:code-array" {...props}></Icon>
