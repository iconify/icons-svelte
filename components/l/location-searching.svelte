<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ni45svb9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ni45svb9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:location-searching" {...props}></Icon>
