<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o4oe12p6t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o4oe12p6t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:lingarr-light" {...props}></Icon>
