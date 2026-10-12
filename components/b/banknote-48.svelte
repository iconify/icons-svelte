<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/shgfqubvu.css';
import '../../css/b/b101e8_sq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="shgfqubvu"/><path class="b101e8_sq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:banknote-48" {...props}></Icon>
