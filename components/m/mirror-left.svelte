<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r0-p_6bkq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r0-p_6bkq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:mirror-left" {...props}></Icon>
