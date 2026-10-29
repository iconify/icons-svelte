<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uwc2mnb2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uwc2mnb2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:bluetooth-off" {...props}></Icon>
