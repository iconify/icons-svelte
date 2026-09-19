<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pgp1tcvai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="pgp1tcvai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:knexjs" {...props}></Icon>
