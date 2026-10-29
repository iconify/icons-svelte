<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/unuv3bb5t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="unuv3bb5t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:chevrons-left-right" {...props}></Icon>
