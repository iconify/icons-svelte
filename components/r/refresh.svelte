<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e0y7rc81h.css';
import '../../css/s/s-i43gbfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e0y7rc81h"/><path class="s-i43gbfr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:refresh" {...props}></Icon>
