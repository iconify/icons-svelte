<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/to8wr5-fc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary to8wr5-fc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:curtains-duotone" {...props}></Icon>
