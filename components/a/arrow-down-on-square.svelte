<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vgn1g8e1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vgn1g8e1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-down-on-square" {...props}></Icon>
