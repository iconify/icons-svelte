<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zpuc31_wq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zpuc31_wq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:lighthouse" {...props}></Icon>
