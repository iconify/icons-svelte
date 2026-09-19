<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qbar0lbxc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qbar0lbxc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:align-image-center" {...props}></Icon>
