<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cza5jkb3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="cza5jkb3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:portrait" {...props}></Icon>
