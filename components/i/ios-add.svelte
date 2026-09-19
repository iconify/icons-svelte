<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s04b96bxu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s04b96bxu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-add" {...props}></Icon>
