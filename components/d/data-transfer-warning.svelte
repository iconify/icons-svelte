<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/epmzw59au.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="epmzw59au"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:data-transfer-warning" {...props}></Icon>
