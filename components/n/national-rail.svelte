<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gl6i0eb3h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gl6i0eb3h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:national-rail" {...props}></Icon>
