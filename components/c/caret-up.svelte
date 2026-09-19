<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ab5cd6g8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1280};
const content = `<path class="ab5cd6g8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:caret-up" {...props}></Icon>
