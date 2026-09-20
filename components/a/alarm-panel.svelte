<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vbj6ibb7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vbj6ibb7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:alarm-panel" {...props}></Icon>
