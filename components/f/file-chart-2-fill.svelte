<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gz9hxmb4t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gz9hxmb4t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:file-chart-2-fill" {...props}></Icon>
