<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p1ggv-gde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="p1ggv-gde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:braille" {...props}></Icon>
