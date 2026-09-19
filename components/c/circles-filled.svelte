<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k8wx459xs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k8wx459xs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:circles-filled" {...props}></Icon>
