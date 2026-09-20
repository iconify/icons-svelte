<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/izucyb58q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="izucyb58q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:frappe-gameplan-dark" {...props}></Icon>
