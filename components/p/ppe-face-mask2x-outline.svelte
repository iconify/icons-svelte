<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ef9rq8zxh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ef9rq8zxh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:ppe-face-mask2x-outline" {...props}></Icon>
