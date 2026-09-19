<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cc2hi3nnq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cc2hi3nnq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:chevron-right-fill" {...props}></Icon>
