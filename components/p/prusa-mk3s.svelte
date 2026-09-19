<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zfk8_9b1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zfk8_9b1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:prusa-mk3s" {...props}></Icon>
