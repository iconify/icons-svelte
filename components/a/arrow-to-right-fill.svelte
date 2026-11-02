<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ab-d_pbrz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ab-d_pbrz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:arrow-to-right-fill" {...props}></Icon>
