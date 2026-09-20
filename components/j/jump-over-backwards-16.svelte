<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hswgs7b_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hswgs7b_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:jump-over-backwards-16" {...props}></Icon>
