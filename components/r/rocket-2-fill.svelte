<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vscn6xb3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vscn6xb3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:rocket-2-fill" {...props}></Icon>
