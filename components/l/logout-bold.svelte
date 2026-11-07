<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i7wwok4ts.css';
import '../../css/o/otho62bps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i7wwok4ts"/><path class="otho62bps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:logout-bold" {...props}></Icon>
