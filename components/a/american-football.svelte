<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pfltx6dox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pfltx6dox"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:american-football" {...props}></Icon>
