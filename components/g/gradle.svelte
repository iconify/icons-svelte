<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gpqlw8uhg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gpqlw8uhg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:gradle" {...props}></Icon>
