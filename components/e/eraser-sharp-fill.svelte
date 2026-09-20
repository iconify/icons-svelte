<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jkpku9bxr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jkpku9bxr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:eraser-sharp-fill" {...props}></Icon>
