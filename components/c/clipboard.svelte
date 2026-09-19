<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cj9cwm6hq.css';
import '../../css/d/d66d9mkgz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="cj9cwm6hq"/><path class="d66d9mkgz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:clipboard" {...props}></Icon>
