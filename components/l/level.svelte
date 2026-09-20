<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bkcoq_blx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bkcoq_blx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:level" {...props}></Icon>
