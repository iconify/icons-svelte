<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s273e8tgd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s273e8tgd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:button" {...props}></Icon>
