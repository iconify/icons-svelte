<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lk7i4qv0w.css';
import '../../css/b/bu5x6-ooy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lk7i4qv0w"/><path class="bu5x6-ooy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:book" {...props}></Icon>
