<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pa863fofv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pa863fofv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:bolt-circle-filled" {...props}></Icon>
