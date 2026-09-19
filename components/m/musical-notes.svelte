<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/odg8d7b5z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="odg8d7b5z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:musical-notes" {...props}></Icon>
