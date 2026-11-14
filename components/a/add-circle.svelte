<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/owfbccc9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="owfbccc9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:add-circle" {...props}></Icon>
