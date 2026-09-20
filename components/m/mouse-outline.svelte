<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fx-4cl3tk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="fx-4cl3tk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:mouse-outline" {...props}></Icon>
