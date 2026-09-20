<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kq6f6bcoa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kq6f6bcoa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:required" {...props}></Icon>
