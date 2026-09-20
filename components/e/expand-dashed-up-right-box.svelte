<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pkyb-daam.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pkyb-daam"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:expand-dashed-up-right-box" {...props}></Icon>
