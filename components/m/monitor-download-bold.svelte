<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yze9kk29k.css';
import '../../css/v/vojar-box.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yze9kk29k"/><path class="vojar-box"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:monitor-download-bold" {...props}></Icon>
