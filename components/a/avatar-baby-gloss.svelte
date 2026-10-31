<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cx5164bqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cx5164bqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:avatar-baby-gloss" {...props}></Icon>
