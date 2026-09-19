<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xwyv0accm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="xwyv0accm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:eslint" {...props}></Icon>
