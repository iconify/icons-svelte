<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/abw1ukz-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="abw1ukz-q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:grid-squares-sharp" {...props}></Icon>
