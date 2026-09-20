<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dj4jy0b8n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="dj4jy0b8n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:layers-union-solid" {...props}></Icon>
