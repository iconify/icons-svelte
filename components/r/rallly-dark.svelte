<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h9woi6bez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h9woi6bez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rallly-dark" {...props}></Icon>
