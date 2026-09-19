<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a9dfu13yp.css';
import '../../css/b/bn6ebpb5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a9dfu13yp"/><path class="bn6ebpb5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-up-right-stroke-square" {...props}></Icon>
