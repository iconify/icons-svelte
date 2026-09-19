<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pk-u7ac7z.css';
import '../../css/h/h3iug1uno.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="pk-u7ac7z"/><path class="h3iug1uno"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:lodash" {...props}></Icon>
