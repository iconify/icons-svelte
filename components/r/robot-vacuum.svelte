<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q3f6o9_to.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q3f6o9_to"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:robot-vacuum" {...props}></Icon>
