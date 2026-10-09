<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ritkb0p_x.css';
import '../../css/w/wp6vfybzd.css';
import '../../css/j/jgrjg5bie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ritkb0p_x"/><path class="wp6vfybzd"/><path class="jgrjg5bie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:arrow-left-right-20" {...props}></Icon>
