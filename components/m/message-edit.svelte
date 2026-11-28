<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipkoobcel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ipkoobcel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:message-edit" {...props}></Icon>
