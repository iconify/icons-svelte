<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nyt5vk0em.css';
import '../../css/a/aj1kvdbma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="nyt5vk0em"/><path class="aj1kvdbma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:alt-text-fill-20" {...props}></Icon>
