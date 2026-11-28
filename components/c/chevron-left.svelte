<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l45my0bsv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l45my0bsv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:chevron-left" {...props}></Icon>
