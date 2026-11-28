<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g5sjvnbab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g5sjvnbab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:champagne-heart" {...props}></Icon>
