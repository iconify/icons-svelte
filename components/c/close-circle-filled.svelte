<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ujm-_ywyx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ujm-_ywyx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:close-circle-filled" {...props}></Icon>
