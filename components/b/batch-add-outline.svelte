<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zm02v-bqq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zm02v-bqq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:batch-add-outline" {...props}></Icon>
