<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ok-_jky8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="ok-_jky8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:chat" {...props}></Icon>
