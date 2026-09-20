<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gaw5a66hh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gaw5a66hh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:arrow-left-down-linear" {...props}></Icon>
