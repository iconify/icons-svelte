<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/esuzo23md.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="esuzo23md"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:image-star" {...props}></Icon>
