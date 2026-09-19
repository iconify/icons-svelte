<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x87cd2g6x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x87cd2g6x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:garbage-plastic" {...props}></Icon>
