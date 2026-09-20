<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mqw0mabke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mqw0mabke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:printer-pos-remove" {...props}></Icon>
