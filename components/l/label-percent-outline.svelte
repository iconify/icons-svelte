<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fjjqdxf4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fjjqdxf4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:label-percent-outline" {...props}></Icon>
