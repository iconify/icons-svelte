<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kd6bc6ohl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kd6bc6ohl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:redo-line" {...props}></Icon>
