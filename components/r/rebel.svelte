<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lxvcj4bqd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lxvcj4bqd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:rebel" {...props}></Icon>
