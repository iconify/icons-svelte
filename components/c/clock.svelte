<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hmk826btk.css';
import '../../css/f/f6hca-bnv.css';
import '../../css/f/fpr104b-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="hmk826btk"/><path class="f6hca-bnv"/><path class="fpr104b-q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:clock" {...props}></Icon>
