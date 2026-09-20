<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ki8ssi60z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ki8ssi60z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:riding-line" {...props}></Icon>
