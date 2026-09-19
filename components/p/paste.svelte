<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jre1oib0e.css';
import '../../css/v/vdbqspb8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jre1oib0e"/><path class="vdbqspb8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:paste" {...props}></Icon>
