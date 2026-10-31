<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wt3ij9b8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wt3ij9b8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:remove-formatting-fill-round" {...props}></Icon>
