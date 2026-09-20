<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/phz5pab0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="phz5pab0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:raindrops" {...props}></Icon>
