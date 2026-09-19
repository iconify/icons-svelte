<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u20q-_bqv.css';
import '../../css/h/hmk826btk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="u20q-_bqv"/><path class="hmk826btk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:remove" {...props}></Icon>
