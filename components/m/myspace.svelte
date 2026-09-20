<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m92zj5l4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m92zj5l4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:myspace" {...props}></Icon>
