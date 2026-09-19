<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_x-m7_yy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="y_x-m7_yy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:fastright" {...props}></Icon>
