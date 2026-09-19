<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ksu31ioyl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b ksu31ioyl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:circle-dashed-half-filled" {...props}></Icon>
