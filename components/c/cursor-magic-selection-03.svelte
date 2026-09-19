<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n6ymjubyz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n6ymjubyz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:cursor-magic-selection-03" {...props}></Icon>
