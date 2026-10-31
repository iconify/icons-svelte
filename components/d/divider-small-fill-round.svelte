<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/er3-szkyi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="er3-szkyi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:divider-small-fill-round" {...props}></Icon>
