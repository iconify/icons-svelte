<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i8krpkbpq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="i8krpkbpq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:keycap-fn-small" {...props}></Icon>
