<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ja4f5ybie.css';
import '../../css/u/ug7yt43lf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ja4f5ybie"/><path class="ug7yt43lf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:microplastics-48" {...props}></Icon>
