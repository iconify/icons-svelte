<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lsogi6bkr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="lsogi6bkr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:hangout" {...props}></Icon>
