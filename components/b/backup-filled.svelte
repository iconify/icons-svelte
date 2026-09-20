<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hcu5g6baw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hcu5g6baw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:backup-filled" {...props}></Icon>
