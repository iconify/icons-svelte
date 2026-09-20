<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mxxrf2bwp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mxxrf2bwp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:message-square-plus" {...props}></Icon>
