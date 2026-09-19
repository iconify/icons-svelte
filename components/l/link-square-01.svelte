<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yw0eq05ko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yw0eq05ko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:link-square-01" {...props}></Icon>
