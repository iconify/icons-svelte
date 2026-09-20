<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/caf2-sbzm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="caf2-sbzm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:arrow-right-to-line" {...props}></Icon>
