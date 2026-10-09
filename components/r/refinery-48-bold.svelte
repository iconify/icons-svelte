<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eojz8nbhf.css';
import '../../css/l/lalcw8bzw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="eojz8nbhf"/><path class="lalcw8bzw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:refinery-48-bold" {...props}></Icon>
