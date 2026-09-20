<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u563jbcsc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u563jbcsc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:cloud-mist-2-bold" {...props}></Icon>
