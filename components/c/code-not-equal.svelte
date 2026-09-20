<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vvck6j57a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vvck6j57a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:code-not-equal" {...props}></Icon>
