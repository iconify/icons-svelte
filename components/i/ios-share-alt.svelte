<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/grmy6--qt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="grmy6--qt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-share-alt" {...props}></Icon>
