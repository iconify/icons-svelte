<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bjgc9gb-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":24};
const content = `<path class="bjgc9gb-q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:foursquare" {...props}></Icon>
