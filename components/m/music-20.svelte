<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zaigx2b8t.css';
import '../../css/l/lj4fzeu5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="zaigx2b8t"/><path class="lj4fzeu5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:music-20" {...props}></Icon>
