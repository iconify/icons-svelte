<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y6jndybtz.css';
import '../../css/o/ocih1mz8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y6jndybtz"/><path class="ocih1mz8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:network-browser-bold" {...props}></Icon>
