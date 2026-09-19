<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iug3cpbpr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="iug3cpbpr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:mongock" {...props}></Icon>
