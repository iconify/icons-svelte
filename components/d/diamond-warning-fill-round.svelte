<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ekrb82o1y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ekrb82o1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:diamond-warning-fill-round" {...props}></Icon>
