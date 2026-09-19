<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eln8b-54w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":13,"height":24};
const content = `<path class="eln8b-54w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:bookmark-alt" {...props}></Icon>
