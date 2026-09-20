<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j00ef2i9a.css';
import '../../css/v/vje10cmgc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j00ef2i9a"/><path class="vje10cmgc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:activity-filled" {...props}></Icon>
