<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cxds1i0dj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cxds1i0dj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:mchc" {...props}></Icon>
