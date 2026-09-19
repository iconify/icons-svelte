<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hr2fgtbnx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="hr2fgtbnx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:feathersjs" {...props}></Icon>
