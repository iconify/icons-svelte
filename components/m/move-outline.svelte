<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i6ychc3fo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i6ychc3fo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:move-outline" {...props}></Icon>
