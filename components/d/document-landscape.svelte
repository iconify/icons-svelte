<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/blbu05bix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="blbu05bix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:document-landscape" {...props}></Icon>
