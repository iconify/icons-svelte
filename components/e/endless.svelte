<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wvuw5pf8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wvuw5pf8y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:endless" {...props}></Icon>
