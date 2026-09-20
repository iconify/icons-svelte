<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f46n3wgqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f46n3wgqa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:l3x" {...props}></Icon>
