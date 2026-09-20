<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mxav8w73h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mxav8w73h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:logout-circle-fill" {...props}></Icon>
