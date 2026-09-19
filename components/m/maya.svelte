<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xfasz3buw.css';
import '../../css/i/iu6mn3bmp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="xfasz3buw"/><path class="iu6mn3bmp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:maya" {...props}></Icon>
