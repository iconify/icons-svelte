<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g712bfbaj.css';
import '../../css/h/hy4qzjznx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g712bfbaj"/><path class="hy4qzjznx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:alarm-alt" {...props}></Icon>
