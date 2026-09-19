<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nvhljtbdd.css';
import '../../css/d/dwu99p9fj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="nvhljtbdd"/><path class="dwu99p9fj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:picture" {...props}></Icon>
