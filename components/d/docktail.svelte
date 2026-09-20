<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w93zx82mi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w93zx82mi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:docktail" {...props}></Icon>
