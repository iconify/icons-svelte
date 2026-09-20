<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l2w919zsd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l2w919zsd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:arrow-down-right-dashed-panel-fill" {...props}></Icon>
