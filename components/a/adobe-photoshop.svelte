<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_ufcgbbq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="d_ufcgbbq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:adobe-photoshop" {...props}></Icon>
