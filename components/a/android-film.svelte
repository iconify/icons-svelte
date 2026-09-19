<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gix87escz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gix87escz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:android-film" {...props}></Icon>
