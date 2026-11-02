<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/caag8rbrz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="caag8rbrz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:circle-arrow-out-up-right-fill" {...props}></Icon>
