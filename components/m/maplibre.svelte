<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k8h4q4b5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k8h4q4b5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:maplibre" {...props}></Icon>
