<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jwgv7ib-v.css';
import '../../css/i/is5lj6bol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jwgv7ib-v"/><path class="is5lj6bol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:environmental-impact-48-bold" {...props}></Icon>
