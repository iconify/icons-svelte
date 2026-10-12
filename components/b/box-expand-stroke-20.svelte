<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qaweymbez.css';
import '../../css/i/iemqaibxb.css';
import '../../css/b/bag-f3b3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qaweymbez"/><path class="iemqaibxb"/><path class="bag-f3b3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:box-expand-stroke-20" {...props}></Icon>
