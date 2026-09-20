<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s0l1-gtup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s0l1-gtup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:immer" {...props}></Icon>
