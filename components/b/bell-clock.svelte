<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z2-3iqd1a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z2-3iqd1a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:bell-clock" {...props}></Icon>
