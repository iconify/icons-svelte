<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ngec0_l4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ngec0_l4r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:link-vertical" {...props}></Icon>
