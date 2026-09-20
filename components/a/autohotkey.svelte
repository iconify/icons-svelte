<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i1n3j_hwz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i1n3j_hwz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:autohotkey" {...props}></Icon>
