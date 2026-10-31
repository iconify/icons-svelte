<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rdf4o6ifl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rdf4o6ifl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:list-ordered-duotone-round" {...props}></Icon>
