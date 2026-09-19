<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_2evxb0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":512};
const content = `<path class="c_2evxb0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:creative-commons-remix" {...props}></Icon>
