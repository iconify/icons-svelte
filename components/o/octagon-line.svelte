<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s5qmm2sbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s5qmm2sbc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:octagon-line" {...props}></Icon>
