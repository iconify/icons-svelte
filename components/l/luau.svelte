<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c13o2wbqp.css';
import '../../css/t/tnle1tu0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="c13o2wbqp"/><path class="tnle1tu0a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:luau" {...props}></Icon>
