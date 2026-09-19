<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b85wjpb7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b85wjpb7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:android-arrow-dropdown-circle" {...props}></Icon>
