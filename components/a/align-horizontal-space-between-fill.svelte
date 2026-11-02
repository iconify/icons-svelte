<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p6a3wwbht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p6a3wwbht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:align-horizontal-space-between-fill" {...props}></Icon>
