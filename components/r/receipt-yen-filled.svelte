<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yiho0ob9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yiho0ob9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:receipt-yen-filled" {...props}></Icon>
