<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bf6zq1beg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bf6zq1beg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:grid-squares-x-sharp" {...props}></Icon>
