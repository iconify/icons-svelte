<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vjugphbbc.css';
import '../../css/u/u5yldcb3g.css';
import '../../css/f/fip9ksb8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vjugphbbc"/><path class="u5yldcb3g"/><path class="fip9ksb8z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:moon-star-48" {...props}></Icon>
