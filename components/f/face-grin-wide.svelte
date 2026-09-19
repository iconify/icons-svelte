<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hb6yle7hb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="hb6yle7hb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:face-grin-wide" {...props}></Icon>
