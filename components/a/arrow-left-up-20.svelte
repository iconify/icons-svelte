<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pdylnj5ie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="pdylnj5ie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:arrow-left-up-20" {...props}></Icon>
