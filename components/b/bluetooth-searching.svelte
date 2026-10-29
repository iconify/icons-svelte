<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ry82r9o5t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ry82r9o5t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:bluetooth-searching" {...props}></Icon>
