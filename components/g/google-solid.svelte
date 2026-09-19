<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/na3cc9g2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="na3cc9g2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:google-solid" {...props}></Icon>
