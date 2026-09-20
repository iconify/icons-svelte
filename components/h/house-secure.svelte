<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s524j1nso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s524j1nso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:house-secure" {...props}></Icon>
