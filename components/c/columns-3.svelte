<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tmscxibfq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tmscxibfq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:columns-3" {...props}></Icon>
