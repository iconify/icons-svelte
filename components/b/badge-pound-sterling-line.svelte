<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ka7cagbdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ka7cagbdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:badge-pound-sterling-line" {...props}></Icon>
