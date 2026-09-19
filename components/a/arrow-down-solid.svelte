<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ie4bjn88h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ie4bjn88h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-down-solid" {...props}></Icon>
