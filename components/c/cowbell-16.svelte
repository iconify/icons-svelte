<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sb6u6tbuf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="sb6u6tbuf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:cowbell-16" {...props}></Icon>
