<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bsmsgz_jk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bsmsgz_jk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:ad-circle-off-fill" {...props}></Icon>
