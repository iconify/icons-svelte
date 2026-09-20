<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dvypck91m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dvypck91m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:ign" {...props}></Icon>
