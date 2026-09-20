<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ewqdwvung.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="ewqdwvung"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:dollar" {...props}></Icon>
