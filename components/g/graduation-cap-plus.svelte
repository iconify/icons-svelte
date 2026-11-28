<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wpzvpbxru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wpzvpbxru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:graduation-cap-plus" {...props}></Icon>
