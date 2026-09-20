<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nzbf_mj_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nzbf_mj_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:folder-fill" {...props}></Icon>
