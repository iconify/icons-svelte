<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sdh6q3bfd.css';
import '../../css/w/wxyj37b4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="sdh6q3bfd"/><path class="wxyj37b4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chimney-48-bold" {...props}></Icon>
