<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iarxcvbzs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iarxcvbzs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:flag-triangle-left" {...props}></Icon>
