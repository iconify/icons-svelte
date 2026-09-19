<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u1o22uoyp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="u1o22uoyp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:flying-saucer" {...props}></Icon>
