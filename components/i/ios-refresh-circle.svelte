<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o5281sv4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o5281sv4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-refresh-circle" {...props}></Icon>
