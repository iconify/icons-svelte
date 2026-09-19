<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/casympb6z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="casympb6z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:disc" {...props}></Icon>
