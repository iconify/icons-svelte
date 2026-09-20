<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wt01g1b5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wt01g1b5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:database-2" {...props}></Icon>
