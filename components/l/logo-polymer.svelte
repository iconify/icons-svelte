<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jo87m9b3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jo87m9b3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:logo-polymer" {...props}></Icon>
