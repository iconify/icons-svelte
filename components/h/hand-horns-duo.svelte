<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h8hps5hrz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="h8hps5hrz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:hand-horns-duo" {...props}></Icon>
