<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/abozm7xon.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="abozm7xon"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:firezone" {...props}></Icon>
