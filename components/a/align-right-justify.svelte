<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dd_buyb8k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dd_buyb8k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:align-right-justify" {...props}></Icon>
