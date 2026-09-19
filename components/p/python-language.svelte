<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jav2add5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="jav2add5d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:python-language" {...props}></Icon>
