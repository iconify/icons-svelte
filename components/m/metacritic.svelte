<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a--a4pxgf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a--a4pxgf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:metacritic" {...props}></Icon>
