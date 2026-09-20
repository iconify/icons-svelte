<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jd4435b7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jd4435b7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:bash-dark" {...props}></Icon>
