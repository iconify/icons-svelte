<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi9cg7bus.css';
import '../../css/c/c6xz9rq9g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bi9cg7bus"/><path class="c6xz9rq9g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:connectwise-screenconnect-dark" {...props}></Icon>
