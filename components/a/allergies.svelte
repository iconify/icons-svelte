<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jmp39m8qx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="jmp39m8qx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:allergies" {...props}></Icon>
