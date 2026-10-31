<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j2xzm_b_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j2xzm_b_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:reload-alt-duocolor-round" {...props}></Icon>
