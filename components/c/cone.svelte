<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k72lseb_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="k72lseb_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:cone" {...props}></Icon>
