<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/by007idoi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="by007idoi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-up-drop-circle-outline" {...props}></Icon>
