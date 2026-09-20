<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rdrja8e0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rdrja8e0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:arrow-down-24" {...props}></Icon>
