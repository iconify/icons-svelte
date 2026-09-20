<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/by6okx3ib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="by6okx3ib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:currency-won-2-line" {...props}></Icon>
