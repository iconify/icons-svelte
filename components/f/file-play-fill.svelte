<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nvbm_uvgv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nvbm_uvgv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:file-play-fill" {...props}></Icon>
