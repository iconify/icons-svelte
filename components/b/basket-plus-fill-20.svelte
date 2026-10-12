<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lxm-7vagy.css';
import '../../css/r/r3cn_9bmy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lxm-7vagy"/><path class="r3cn_9bmy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:basket-plus-fill-20" {...props}></Icon>
