<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x9x0xabde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x9x0xabde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:alphabet-v-box" {...props}></Icon>
