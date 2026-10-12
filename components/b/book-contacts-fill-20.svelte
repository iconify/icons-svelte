<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bfnvfbc2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="bfnvfbc2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:book-contacts-fill-20" {...props}></Icon>
