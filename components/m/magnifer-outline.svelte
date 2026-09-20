<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hd9w4b9sz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hd9w4b9sz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:magnifer-outline" {...props}></Icon>
