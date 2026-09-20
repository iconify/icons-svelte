<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u4j0rxb5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u4j0rxb5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:panels-right-bottom-sharp" {...props}></Icon>
