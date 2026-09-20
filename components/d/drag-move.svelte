<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s248fhbsg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s248fhbsg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:drag-move" {...props}></Icon>
