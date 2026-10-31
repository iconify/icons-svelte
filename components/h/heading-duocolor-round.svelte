<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xsqjwc90j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xsqjwc90j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:heading-duocolor-round" {...props}></Icon>
