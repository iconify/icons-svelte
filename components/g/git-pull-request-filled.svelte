<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v06x-3-pj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v06x-3-pj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:git-pull-request-filled" {...props}></Icon>
