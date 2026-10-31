<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uiprb2byv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uiprb2byv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:pill-round" {...props}></Icon>
