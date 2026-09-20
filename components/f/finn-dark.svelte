<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_tvfq6mb.css';
import '../../css/t/tfa5mdbsb.css';
import '../../css/i/iufs412sl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c_tvfq6mb"/><path class="tfa5mdbsb"/><path class="iufs412sl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:finn-dark" {...props}></Icon>
