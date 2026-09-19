<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rimzogy_d.css';
import '../../css/x/xkpcfdb4u.css';
import '../../css/h/hasg0ee8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="rimzogy_d"/><path class="xkpcfdb4u"/><circle class="hasg0ee8z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:info" {...props}></Icon>
