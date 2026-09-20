<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bt08a3bkh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bt08a3bkh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:chevron-left" {...props}></Icon>
