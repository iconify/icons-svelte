<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mv1vq517n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mv1vq517n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:cloud-upload" {...props}></Icon>
