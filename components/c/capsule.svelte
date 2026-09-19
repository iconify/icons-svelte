<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/afyho6bfv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="afyho6bfv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:capsule" {...props}></Icon>
