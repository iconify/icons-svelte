<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jks_f3kme.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jks_f3kme"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:font-size" {...props}></Icon>
