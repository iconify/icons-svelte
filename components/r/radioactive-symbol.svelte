<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xbgmpqbct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xbgmpqbct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:radioactive-symbol" {...props}></Icon>
