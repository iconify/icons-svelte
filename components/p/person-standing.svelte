<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kz0zt2bpu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kz0zt2bpu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:person-standing" {...props}></Icon>
