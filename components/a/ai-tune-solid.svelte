<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ezyrsyb9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ezyrsyb9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:ai-tune-solid" {...props}></Icon>
