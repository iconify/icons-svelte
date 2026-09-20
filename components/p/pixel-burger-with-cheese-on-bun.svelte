<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jsx5tmbnw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="jsx5tmbnw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:pixel-burger-with-cheese-on-bun" {...props}></Icon>
