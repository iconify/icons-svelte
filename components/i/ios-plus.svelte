<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uc0hbgbyr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uc0hbgbyr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-plus" {...props}></Icon>
