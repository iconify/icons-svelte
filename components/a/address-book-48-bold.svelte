<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/djvqpt-nt.css';
import '../../css/i/i3kvsjzmy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="djvqpt-nt"/><path class="i3kvsjzmy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:address-book-48-bold" {...props}></Icon>
