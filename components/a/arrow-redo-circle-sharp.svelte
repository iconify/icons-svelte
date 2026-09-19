<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e2b3vi6yu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e2b3vi6yu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:arrow-redo-circle-sharp" {...props}></Icon>
