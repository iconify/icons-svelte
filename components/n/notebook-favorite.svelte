<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fd-l0acho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fd-l0acho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:notebook-favorite" {...props}></Icon>
