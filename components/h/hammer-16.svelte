<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/is0lndb4h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="is0lndb4h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:hammer-16" {...props}></Icon>
