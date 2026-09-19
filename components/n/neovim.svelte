<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qa5ccwb9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="qa5ccwb9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:neovim" {...props}></Icon>
