<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/st43rpbtf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="st43rpbtf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:classify-add-2-fill" {...props}></Icon>
