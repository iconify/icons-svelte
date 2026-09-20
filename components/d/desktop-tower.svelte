<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uoftywl2f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uoftywl2f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:desktop-tower" {...props}></Icon>
