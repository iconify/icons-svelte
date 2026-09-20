<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gbx2phzgt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gbx2phzgt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:edit-box-fill" {...props}></Icon>
