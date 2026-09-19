<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/glf25bblo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="glf25bblo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:ceylon" {...props}></Icon>
