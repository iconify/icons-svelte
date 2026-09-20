<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gqu5lsb_r.css';
import '../../css/e/e09mkx9uq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gqu5lsb_r"/><path clip-rule="evenodd" class="e09mkx9uq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:reddit" {...props}></Icon>
