<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/po4ezxent.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="po4ezxent"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:file-info-alt" {...props}></Icon>
