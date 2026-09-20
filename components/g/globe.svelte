<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o_ipo_afu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o_ipo_afu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:globe" {...props}></Icon>
