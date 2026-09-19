<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y6pslhx0v.css';
import '../../css/g/gboct0b5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="y6pslhx0v"/><path clip-rule="evenodd" class="gboct0b5i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:atom-wordmark" {...props}></Icon>
