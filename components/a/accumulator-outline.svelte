<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hq6gvzb2k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hq6gvzb2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:accumulator-outline" {...props}></Icon>
