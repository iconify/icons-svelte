<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dhtb0jn5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dhtb0jn5l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:hesa-warning-outline" {...props}></Icon>
