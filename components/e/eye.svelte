<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ek-ptob2h.css';
import '../../css/v/vvuy5gbwu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":24};
const content = `<path class="ek-ptob2h"/><path class="vvuy5gbwu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:eye" {...props}></Icon>
