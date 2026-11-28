<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qtar19kwv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qtar19kwv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:monitor-off" {...props}></Icon>
