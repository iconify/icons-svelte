<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n6gpl0b0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n6gpl0b0a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:arrow-top-left-5-circle-fill" {...props}></Icon>
