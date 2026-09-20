<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/etmml3bly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="etmml3bly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:researchgate" {...props}></Icon>
