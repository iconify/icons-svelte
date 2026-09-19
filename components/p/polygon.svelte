<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l859wrbqw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="l859wrbqw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:polygon" {...props}></Icon>
