<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bo-i2pb8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bo-i2pb8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:books" {...props}></Icon>
