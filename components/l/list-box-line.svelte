<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kfw00t5tm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kfw00t5tm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:list-box-line" {...props}></Icon>
