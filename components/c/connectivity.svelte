<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h1pqfnb0z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h1pqfnb0z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:connectivity" {...props}></Icon>
