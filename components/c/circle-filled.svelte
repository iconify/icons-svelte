<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v1czvcbvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v1czvcbvd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:circle-filled" {...props}></Icon>
