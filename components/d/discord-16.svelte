<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q3j5tbb3r.css';
import '../../css/p/p1hlxdb5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="q3j5tbb3r"/><path clip-rule="evenodd" class="p1hlxdb5d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:discord-16" {...props}></Icon>
