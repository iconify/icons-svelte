<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jl9n98xsl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="jl9n98xsl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:font-awesome-flag" {...props}></Icon>
