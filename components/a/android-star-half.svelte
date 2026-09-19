<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u8e41s75w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u8e41s75w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:android-star-half" {...props}></Icon>
