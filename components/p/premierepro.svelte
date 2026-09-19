<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ltghsnbbc.css';
import '../../css/s/spcgr69nj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="ltghsnbbc"/><path class="spcgr69nj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:premierepro" {...props}></Icon>
