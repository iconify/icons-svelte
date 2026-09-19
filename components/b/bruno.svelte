<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z6gg0ibok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="z6gg0ibok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:bruno" {...props}></Icon>
