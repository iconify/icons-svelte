<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qd-f8lbjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="qd-f8lbjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:percent-badge-20-solid" {...props}></Icon>
