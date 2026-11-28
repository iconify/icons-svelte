<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uwb5omtzc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uwb5omtzc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:globe-search" {...props}></Icon>
