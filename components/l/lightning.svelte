<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c1kwab81w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":352,"height":512};
const content = `<path class="c1kwab81w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:lightning" {...props}></Icon>
