<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u7gn9tbal.css';
import '../../css/j/j3epy4b7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u7gn9tbal"/><path clip-rule="evenodd" class="j3epy4b7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:medal-ribbon-star-bold" {...props}></Icon>
