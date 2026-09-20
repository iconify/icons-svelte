<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zg9ihxbsk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zg9ihxbsk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:paste-outline" {...props}></Icon>
