<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yj5h5m4vp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="yj5h5m4vp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:dot-grid" {...props}></Icon>
