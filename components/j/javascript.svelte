<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/efz0tq6mc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="efz0tq6mc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:javascript" {...props}></Icon>
