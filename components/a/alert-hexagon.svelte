<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rd086ccbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rd086ccbz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:alert-hexagon" {...props}></Icon>
