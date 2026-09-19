<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o75-enbjh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o75-enbjh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-message-rounded-x" {...props}></Icon>
