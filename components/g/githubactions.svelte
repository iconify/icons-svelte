<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l8g3supcw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="l8g3supcw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:githubactions" {...props}></Icon>
