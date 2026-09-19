<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/ql1oq3bqg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ql1oq3bqg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:cloud-arrow-down" {...props}></Icon>
