<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v25lyabxp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v25lyabxp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:equal-not" {...props}></Icon>
