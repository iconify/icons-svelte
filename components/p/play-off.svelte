<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eib1g-bgd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eib1g-bgd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:play-off" {...props}></Icon>
