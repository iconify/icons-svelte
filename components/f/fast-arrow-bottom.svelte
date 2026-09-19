<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qrul7pbzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qrul7pbzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:fast-arrow-bottom" {...props}></Icon>
