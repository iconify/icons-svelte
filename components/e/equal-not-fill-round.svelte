<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/na57upbcn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="na57upbcn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:equal-not-fill-round" {...props}></Icon>
