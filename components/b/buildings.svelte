<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fct5sud1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fct5sud1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:buildings" {...props}></Icon>
