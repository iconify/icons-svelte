<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ug42kdbjz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ug42kdbjz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:flag-gloss" {...props}></Icon>
