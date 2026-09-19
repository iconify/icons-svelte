<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cvqm_db9h.css';
import '../../css/h/hd2zslizq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cvqm_db9h"/><path class="hd2zslizq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:openfilefolder" {...props}></Icon>
