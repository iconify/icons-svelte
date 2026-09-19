<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zuj2j6pai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zuj2j6pai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:ceiling-lamp" {...props}></Icon>
