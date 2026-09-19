<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gzzwzsb-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gzzwzsb-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:rewind-right-fill" {...props}></Icon>
