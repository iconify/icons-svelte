<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n9tgqub2z.css';
import '../../css/l/l8g3b28gy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="n9tgqub2z"/><path class="l8g3b28gy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:address-book-48" {...props}></Icon>
