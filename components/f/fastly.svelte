<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lhh6-acix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lhh6-acix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:fastly" {...props}></Icon>
