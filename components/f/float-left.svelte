<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qr8mm2bst.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qr8mm2bst"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:float-left" {...props}></Icon>
