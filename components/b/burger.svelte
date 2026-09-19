<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x8o-2rgnf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x8o-2rgnf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:burger" {...props}></Icon>
