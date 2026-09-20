<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wkx42b5na.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wkx42b5na"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:number-12-small" {...props}></Icon>
