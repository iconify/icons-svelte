<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wpe5qmjmf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wpe5qmjmf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:airpods-sharp-fill" {...props}></Icon>
