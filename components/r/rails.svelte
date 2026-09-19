<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h3y_m2brn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path clip-rule="evenodd" class="h3y_m2brn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:rails" {...props}></Icon>
