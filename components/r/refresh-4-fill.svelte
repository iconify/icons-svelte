<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m_0kicbjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m_0kicbjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:refresh-4-fill" {...props}></Icon>
