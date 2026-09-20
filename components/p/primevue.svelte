<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ds5-4bcso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ds5-4bcso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:primevue" {...props}></Icon>
