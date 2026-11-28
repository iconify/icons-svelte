<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ooa4c13xh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ooa4c13xh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:graduation-cap-check" {...props}></Icon>
