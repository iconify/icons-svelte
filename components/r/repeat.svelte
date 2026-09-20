<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ld1h7vbcz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ld1h7vbcz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:repeat" {...props}></Icon>
