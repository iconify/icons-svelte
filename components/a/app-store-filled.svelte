<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bffeugi-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="bffeugi-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:app-store-filled" {...props}></Icon>
