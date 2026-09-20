<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nv_7k8bzx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="nv_7k8bzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:plus-circle" {...props}></Icon>
