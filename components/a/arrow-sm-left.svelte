<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qwmr27bhu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="qwmr27bhu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:arrow-sm-left" {...props}></Icon>
