<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g9jmoj0eq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g9jmoj0eq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cursor-default-click" {...props}></Icon>
