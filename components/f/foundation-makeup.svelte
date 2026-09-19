<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gj7drebbn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="gj7drebbn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:foundation-makeup" {...props}></Icon>
