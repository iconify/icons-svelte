<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ht78eobpe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ht78eobpe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:nodebb" {...props}></Icon>
