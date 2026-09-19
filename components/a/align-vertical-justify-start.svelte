<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-vjtvv7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k-vjtvv7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:align-vertical-justify-start" {...props}></Icon>
