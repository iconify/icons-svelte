<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/npdkz94bu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="npdkz94bu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:funnel-light" {...props}></Icon>
