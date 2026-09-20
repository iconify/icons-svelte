<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z2-3_acbf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z2-3_acbf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:behance" {...props}></Icon>
