<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v8n5t8baq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v8n5t8baq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:radio-checked-fill-round" {...props}></Icon>
