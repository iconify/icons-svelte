<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pr52f_b5y.css';
import '../../css/f/fngfi_ztl.css';
import '../../css/p/psdf5lb4l.css';
import '../../css/h/h7bcztycq.css';
import '../../css/t/t6c8t7gok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="pr52f_b5y"><path class="fngfi_ztl"/><path class="psdf5lb4l"/><path class="h7bcztycq"/><path class="t6c8t7gok"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:exchange-outline" {...props}></Icon>
