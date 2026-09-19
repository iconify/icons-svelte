<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x1qja4bht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x1qja4bht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:fire-hazard" {...props}></Icon>
