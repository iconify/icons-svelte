<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/btn1pnkzi.css';
import '../../css/c/c9jj_-b_j.css';
import '../../css/g/gniowmb9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="btn1pnkzi"/><path class="c9jj_-b_j"/><path class="gniowmb9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:data-board" {...props}></Icon>
