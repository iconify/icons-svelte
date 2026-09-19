<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gs9wqcb5y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gs9wqcb5y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:align-horizontal-justify-start" {...props}></Icon>
