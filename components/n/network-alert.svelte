<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k8sr66f0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k8sr66f0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:network-alert" {...props}></Icon>
