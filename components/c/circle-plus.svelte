<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u20q-_bqv.css';
import '../../css/o/ohfddi_sq.css';
import '../../css/h/hmk826btk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="u20q-_bqv"/><path class="ohfddi_sq"/><path class="hmk826btk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:circle-plus" {...props}></Icon>
