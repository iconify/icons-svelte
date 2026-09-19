<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/w/wphs3ib7r.css';
import '../../css/l/lw4genb2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="n1lsf0bnc"><path class="wphs3ib7r"/><path class="lw4genb2l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:box-arrow-up" {...props}></Icon>
