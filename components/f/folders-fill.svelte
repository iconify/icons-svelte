<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k__m-r_jg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k__m-r_jg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:folders-fill" {...props}></Icon>
