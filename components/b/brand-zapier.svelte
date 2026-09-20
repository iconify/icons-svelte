<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jy2v1xbjj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jy2v1xbjj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-zapier" {...props}></Icon>
