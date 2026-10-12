<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hl5v1rsmq.css';
import '../../css/v/v9rv_hbmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hl5v1rsmq"/><path class="v9rv_hbmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:key-stroke-20" {...props}></Icon>
