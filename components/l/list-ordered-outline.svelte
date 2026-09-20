<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v4s73cbnw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="v4s73cbnw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:list-ordered-outline" {...props}></Icon>
