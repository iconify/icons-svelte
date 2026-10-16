<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r3fak-24z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="r3fak-24z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:crusher-48" {...props}></Icon>
