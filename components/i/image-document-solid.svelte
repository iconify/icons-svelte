<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c57dn841e.css';
import '../../css/z/z31349b3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="c57dn841e"/><path class="z31349b3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:image-document-solid" {...props}></Icon>
