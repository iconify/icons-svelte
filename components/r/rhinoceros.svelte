<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o1j-qlvgc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o1j-qlvgc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:rhinoceros" {...props}></Icon>
