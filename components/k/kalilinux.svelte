<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jajfe5b9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="jajfe5b9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:kalilinux" {...props}></Icon>
