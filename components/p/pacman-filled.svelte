<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k8ncm5byz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k8ncm5byz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:pacman-filled" {...props}></Icon>
