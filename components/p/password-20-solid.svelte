<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o4llcebym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="o4llcebym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:password-20-solid" {...props}></Icon>
