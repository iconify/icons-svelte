<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lmrb1-6bw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lmrb1-6bw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:breakwater" {...props}></Icon>
