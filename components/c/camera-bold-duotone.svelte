<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zvnq9o5sc.css';
import '../../css/s/slns-v7tw.css';
import '../../css/t/tawubeb5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zvnq9o5sc"/><path class="slns-v7tw"/><path clip-rule="evenodd" class="tawubeb5f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:camera-bold-duotone" {...props}></Icon>
