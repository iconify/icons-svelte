<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fqez_59rt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fqez_59rt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:flame-fill" {...props}></Icon>
