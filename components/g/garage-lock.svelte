<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z25e2cb9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z25e2cb9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:garage-lock" {...props}></Icon>
