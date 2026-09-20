<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xhuikybji.css';
import '../../css/s/s3hbfpb2y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="xhuikybji"/><path clip-rule="evenodd" class="s3hbfpb2y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:chatbot-solid" {...props}></Icon>
