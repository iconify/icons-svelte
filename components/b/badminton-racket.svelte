<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cjti-ug9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="cjti-ug9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:badminton-racket" {...props}></Icon>
