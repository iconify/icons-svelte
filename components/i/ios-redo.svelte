<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/alzky0bbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="alzky0bbz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-redo" {...props}></Icon>
