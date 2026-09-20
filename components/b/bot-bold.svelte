<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pemoh6p9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pemoh6p9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bot-bold" {...props}></Icon>
