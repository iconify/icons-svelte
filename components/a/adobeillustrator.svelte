<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y4r20cyaq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y4r20cyaq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:adobeillustrator" {...props}></Icon>
