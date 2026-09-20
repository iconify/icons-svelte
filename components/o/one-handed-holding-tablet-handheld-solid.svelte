<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n550um41m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="n550um41m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:one-handed-holding-tablet-handheld-solid" {...props}></Icon>
