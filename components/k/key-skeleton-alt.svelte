<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xiq3o6eix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xiq3o6eix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uis:key-skeleton-alt" {...props}></Icon>
