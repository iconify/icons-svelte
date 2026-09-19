<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gd8hrac-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gd8hrac-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:pound-filled" {...props}></Icon>
