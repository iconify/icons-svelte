<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k5ym7p8cn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k5ym7p8cn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:dental" {...props}></Icon>
