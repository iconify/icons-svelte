<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dvg-drbfm.css';
import '../../css/f/f0fgz2b6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="dvg-drbfm"/><path class="f0fgz2b6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:api-20-bold" {...props}></Icon>
