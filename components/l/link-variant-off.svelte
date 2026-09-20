<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o32rc1bqm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o32rc1bqm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:link-variant-off" {...props}></Icon>
