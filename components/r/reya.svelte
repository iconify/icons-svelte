<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ey-kzfbim.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ey-kzfbim"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:reya" {...props}></Icon>
