<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o5el1vbof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o5el1vbof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:mushroom-alert" {...props}></Icon>
