<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ijbz8-bgs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="ijbz8-bgs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:first" {...props}></Icon>
