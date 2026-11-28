<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xwn-dpbqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xwn-dpbqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:baby" {...props}></Icon>
