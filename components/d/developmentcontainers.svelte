<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zgamo4zls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zgamo4zls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:developmentcontainers" {...props}></Icon>
