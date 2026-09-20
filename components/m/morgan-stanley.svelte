<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q4b7xbbez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":360,"height":90};
const content = `<path class="q4b7xbbez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:morgan-stanley" {...props}></Icon>
