<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vovxt6bbb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vovxt6bbb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:chevron-left" {...props}></Icon>
