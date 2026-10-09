<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r8cp6cb9j.css';
import '../../css/b/bqwp1jb7n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="r8cp6cb9j"/><path class="bqwp1jb7n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:refresh-20" {...props}></Icon>
