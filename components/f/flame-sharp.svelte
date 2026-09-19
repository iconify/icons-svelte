<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mzlzjbb7f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mzlzjbb7f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:flame-sharp" {...props}></Icon>
