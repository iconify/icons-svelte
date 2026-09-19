<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bmqvwcc6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bmqvwcc6i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:join-right-outer" {...props}></Icon>
