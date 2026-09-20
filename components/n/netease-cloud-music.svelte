<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9dy68d1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y9dy68d1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:netease-cloud-music" {...props}></Icon>
