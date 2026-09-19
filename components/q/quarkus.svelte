<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/djh7c23qx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="djh7c23qx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:quarkus" {...props}></Icon>
