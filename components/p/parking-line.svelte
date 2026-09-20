<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v95e19b1o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v95e19b1o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:parking-line" {...props}></Icon>
