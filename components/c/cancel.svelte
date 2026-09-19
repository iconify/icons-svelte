<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hb3n1kb5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hb3n1kb5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:cancel" {...props}></Icon>
