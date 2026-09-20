<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g2477kbfx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g2477kbfx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:arrow-left-fill" {...props}></Icon>
