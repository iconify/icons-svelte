<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/edmyopiyc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="edmyopiyc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-undo" {...props}></Icon>
