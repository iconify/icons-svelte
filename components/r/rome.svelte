<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jngg2rbis.css';
import '../../css/w/w0onahbsz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jngg2rbis"/><path class="w0onahbsz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:rome" {...props}></Icon>
