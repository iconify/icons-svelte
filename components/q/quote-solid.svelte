<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_53k1-ec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j_53k1-ec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:quote-solid" {...props}></Icon>
