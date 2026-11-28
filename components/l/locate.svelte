<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dr32iuijy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dr32iuijy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:locate" {...props}></Icon>
