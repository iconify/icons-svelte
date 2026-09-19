<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b6kj947-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b6kj947-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:plus-round" {...props}></Icon>
