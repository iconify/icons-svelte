<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lrah4su8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lrah4su8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:forum-subtract" {...props}></Icon>
