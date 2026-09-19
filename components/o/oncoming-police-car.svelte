<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k0hssn4us.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="k0hssn4us"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:oncoming-police-car" {...props}></Icon>
