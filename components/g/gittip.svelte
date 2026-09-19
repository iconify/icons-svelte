<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dfubp8nmo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1536};
const content = `<path class="dfubp8nmo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:gittip" {...props}></Icon>
