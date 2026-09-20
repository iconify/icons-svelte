<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nqr8lfj3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nqr8lfj3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:file-edit" {...props}></Icon>
