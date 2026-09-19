<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ksvv1jbrz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ksvv1jbrz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:android-sunny" {...props}></Icon>
