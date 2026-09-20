<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xu2ow8bpw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xu2ow8bpw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:firo" {...props}></Icon>
