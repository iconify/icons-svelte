<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/azvkn8bxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="azvkn8bxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:decrease-16" {...props}></Icon>
