<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/by3g3qbje.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":429.02,"height":429.02,"left":116,"top":34.49};
const content = `<path class="by3g3qbje"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:mastra-dark" {...props}></Icon>
