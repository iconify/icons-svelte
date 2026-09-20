<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jk3oz7bzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jk3oz7bzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:cell-signal-off" {...props}></Icon>
