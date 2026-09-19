<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b6pkkwb5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b6pkkwb5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-chip" {...props}></Icon>
