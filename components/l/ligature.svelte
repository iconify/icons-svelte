<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-7b34bmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i-7b34bmd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:ligature" {...props}></Icon>
