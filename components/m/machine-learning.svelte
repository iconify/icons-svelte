<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ycs1wjbcq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ycs1wjbcq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:machine-learning" {...props}></Icon>
