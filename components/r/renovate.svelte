<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ei_713ibr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ei_713ibr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:renovate" {...props}></Icon>
