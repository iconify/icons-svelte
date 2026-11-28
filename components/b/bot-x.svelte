<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b01rks9ob.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b01rks9ob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:bot-x" {...props}></Icon>
