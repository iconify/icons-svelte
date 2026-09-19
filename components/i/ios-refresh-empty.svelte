<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bemeq4bko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bemeq4bko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-refresh-empty" {...props}></Icon>
