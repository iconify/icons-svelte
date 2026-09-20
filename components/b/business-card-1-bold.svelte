<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/scks1v4hj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="scks1v4hj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:business-card-1-bold" {...props}></Icon>
