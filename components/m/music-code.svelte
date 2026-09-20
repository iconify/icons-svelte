<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t1ckpi3ti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t1ckpi3ti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:music-code" {...props}></Icon>
