<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/go_uhwbvg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="go_uhwbvg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:question-circle-24px" {...props}></Icon>
