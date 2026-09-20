<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qdv4d22pr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qdv4d22pr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:expand-dashed-up-left-box-sharp" {...props}></Icon>
