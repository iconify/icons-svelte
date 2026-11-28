<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f5tyr8-bq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f5tyr8-bq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:forklift" {...props}></Icon>
