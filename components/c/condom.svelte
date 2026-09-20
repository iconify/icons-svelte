<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/za9cmqb_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="za9cmqb_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:condom" {...props}></Icon>
