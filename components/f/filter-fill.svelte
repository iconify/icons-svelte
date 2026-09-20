<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/slw0lyzha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="slw0lyzha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:filter-fill" {...props}></Icon>
