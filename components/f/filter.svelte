<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xcsnyg2hr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xcsnyg2hr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:filter" {...props}></Icon>
