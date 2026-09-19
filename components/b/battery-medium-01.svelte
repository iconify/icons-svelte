<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ioc0cybks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ioc0cybks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:battery-medium-01" {...props}></Icon>
