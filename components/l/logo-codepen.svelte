<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oxvehrb0j.css';
import '../../css/h/h-13c9bbf.css';
import '../../css/r/r99w2lb9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oxvehrb0j"/><path class="h-13c9bbf"/><path class="r99w2lb9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:logo-codepen" {...props}></Icon>
