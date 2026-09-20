<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cqc2nfbnt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cqc2nfbnt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:presentation-play" {...props}></Icon>
