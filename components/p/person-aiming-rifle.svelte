<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b-0r_040s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="b-0r_040s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-aiming-rifle" {...props}></Icon>
