<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mjj5xkb8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mjj5xkb8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:logstash" {...props}></Icon>
