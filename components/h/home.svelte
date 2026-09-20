<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-fvc70vb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p-fvc70vb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:home" {...props}></Icon>
