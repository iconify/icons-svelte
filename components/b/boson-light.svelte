<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bhsrqh-0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bhsrqh-0t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:boson-light" {...props}></Icon>
