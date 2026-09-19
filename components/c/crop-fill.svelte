<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/maz51bb-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="maz51bb-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:crop-fill" {...props}></Icon>
