<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/irm1bq5fz.css';
import '../../css/w/w9u355bkz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="irm1bq5fz"/><path class="w9u355bkz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:globe" {...props}></Icon>
