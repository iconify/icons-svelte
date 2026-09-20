<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kwr8ainsu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kwr8ainsu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:alphabet-o-box" {...props}></Icon>
