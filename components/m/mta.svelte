<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d1uynmblf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d1uynmblf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:mta" {...props}></Icon>
