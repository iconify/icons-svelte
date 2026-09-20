<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/onvzacbmf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="onvzacbmf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:dot" {...props}></Icon>
