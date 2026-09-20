<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/icbbfbm-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="icbbfbm-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:folder-plus" {...props}></Icon>
