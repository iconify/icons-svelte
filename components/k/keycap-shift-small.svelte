<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gnmz_13kt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="gnmz_13kt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:keycap-shift-small" {...props}></Icon>
