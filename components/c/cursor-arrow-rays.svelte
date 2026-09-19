<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pu67iibzt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pu67iibzt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:cursor-arrow-rays" {...props}></Icon>
