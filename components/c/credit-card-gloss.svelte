<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-yd1ob6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g-yd1ob6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:credit-card-gloss" {...props}></Icon>
