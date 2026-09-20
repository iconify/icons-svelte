<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k1d9xtb6t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="k1d9xtb6t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:edit" {...props}></Icon>
