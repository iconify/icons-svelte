<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/ba2z7ll-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ba2z7ll-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:arrow-rotate-right-20" {...props}></Icon>
