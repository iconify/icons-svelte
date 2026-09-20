<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ifzak3byz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ifzak3byz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:file-restore-outline" {...props}></Icon>
