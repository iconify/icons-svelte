<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ie5gvq08v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1025};
const content = `<path class="ie5gvq08v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:minitonguealt" {...props}></Icon>
