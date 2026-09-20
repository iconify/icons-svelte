<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/et-0ovb7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="et-0ovb7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:bbq" {...props}></Icon>
