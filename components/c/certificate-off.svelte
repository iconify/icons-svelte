<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ehueecc9v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ehueecc9v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:certificate-off" {...props}></Icon>
