<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j7bxye5gu.css';
import '../../css/f/f0tftrz9n.css';
import '../../css/m/m41x7yb6k.css';
import '../../css/o/o1r8z0b3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j7bxye5gu"/><path class="f0tftrz9n"/><path class="m41x7yb6k"/><path class="o1r8z0b3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:quickbars" {...props}></Icon>
