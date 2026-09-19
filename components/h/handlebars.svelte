<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jgifm_d5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="jgifm_d5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:handlebars" {...props}></Icon>
