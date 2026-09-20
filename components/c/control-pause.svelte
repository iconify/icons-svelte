<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lpbz6ib3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="lpbz6ib3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:control-pause" {...props}></Icon>
