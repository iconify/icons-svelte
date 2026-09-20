<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xts0dhppt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xts0dhppt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:file-paper-2-fill" {...props}></Icon>
