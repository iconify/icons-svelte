<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c525gmbvw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":554,"height":137};
const content = `<path class="c525gmbvw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:espn" {...props}></Icon>
