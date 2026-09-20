<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kiqtkgbhk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="kiqtkgbhk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-reaching-into-bins" {...props}></Icon>
