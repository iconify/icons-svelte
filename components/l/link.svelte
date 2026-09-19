<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k7riybc4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="k7riybc4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:link" {...props}></Icon>
