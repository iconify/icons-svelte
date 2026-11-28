<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fk46foz9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fk46foz9e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:garage-lock" {...props}></Icon>
