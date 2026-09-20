<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rfeh19hzz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rfeh19hzz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:mening" {...props}></Icon>
