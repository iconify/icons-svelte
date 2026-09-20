<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nen5y7buo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nen5y7buo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:minima" {...props}></Icon>
