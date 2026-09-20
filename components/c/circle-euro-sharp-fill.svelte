<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ewfz87byp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ewfz87byp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-euro-sharp-fill" {...props}></Icon>
