<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jrfvdrbva.css';
import '../../css/a/avxyqj62k.css';
import '../../css/h/hy5oa6obz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jrfvdrbva"/><path class="avxyqj62k"/><path class="hy5oa6obz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:printer-20-bold" {...props}></Icon>
