<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fj97bxb2b.css';
import '../../css/d/ds5jgsbxn.css';
import '../../css/z/zkybc5m-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fj97bxb2b"/><circle class="ds5jgsbxn"/><path class="zkybc5m-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:kubelet-outlined" {...props}></Icon>
