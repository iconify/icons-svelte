<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g0yudob-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="g0yudob-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:bootstrap" {...props}></Icon>
