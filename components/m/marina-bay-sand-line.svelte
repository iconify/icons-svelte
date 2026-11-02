<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pp5uy7o3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pp5uy7o3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:marina-bay-sand-line" {...props}></Icon>
