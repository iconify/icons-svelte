<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vbat8kbie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vbat8kbie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:headphones-square-outline" {...props}></Icon>
