<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c0-2cj3rc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c0-2cj3rc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-plus-empty" {...props}></Icon>
