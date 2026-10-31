<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fwxn38blb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fwxn38blb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:id-badge-fill-round" {...props}></Icon>
