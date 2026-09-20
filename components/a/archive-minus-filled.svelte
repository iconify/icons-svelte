<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fx03ew4kg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fx03ew4kg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:archive-minus-filled" {...props}></Icon>
