<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aewnve1os.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="aewnve1os"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:databricks-wordmark" {...props}></Icon>
