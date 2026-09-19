<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ya4h8w4gs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ya4h8w4gs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:mode-dark-light" {...props}></Icon>
