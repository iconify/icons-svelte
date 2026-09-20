<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w338884rh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w338884rh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:repeat-off" {...props}></Icon>
