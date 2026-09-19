<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y3kgvnb-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1536};
const content = `<path class="y3kgvnb-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:clock-o" {...props}></Icon>
