<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ppi8ora1y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ppi8ora1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:nodemon" {...props}></Icon>
