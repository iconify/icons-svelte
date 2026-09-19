<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uxologlos.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uxologlos"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-from-bottom-stroke" {...props}></Icon>
