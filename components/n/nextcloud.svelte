<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mr3w9cn8g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mr3w9cn8g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:nextcloud" {...props}></Icon>
