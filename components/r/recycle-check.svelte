<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jmw3_6bzd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jmw3_6bzd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:recycle-check" {...props}></Icon>
