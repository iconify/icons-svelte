<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l8p9iwiog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path clip-rule="evenodd" class="l8p9iwiog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:apache" {...props}></Icon>
