<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z0gzd41up.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z0gzd41up"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:fedex" {...props}></Icon>
