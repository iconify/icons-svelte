<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zg1h2i3ab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="zg1h2i3ab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:circleone" {...props}></Icon>
