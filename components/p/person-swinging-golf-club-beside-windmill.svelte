<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-3huhbtx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="k-3huhbtx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-swinging-golf-club-beside-windmill" {...props}></Icon>
