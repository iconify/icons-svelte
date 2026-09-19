<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lyf6e2qlo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lyf6e2qlo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-warning" {...props}></Icon>
