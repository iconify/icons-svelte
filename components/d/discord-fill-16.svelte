<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_1x7ub7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="a_1x7ub7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:discord-fill-16" {...props}></Icon>
