<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tabpkmb6z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tabpkmb6z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:do-not-disturb-outline" {...props}></Icon>
