<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lbi9hljjd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lbi9hljjd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:file-xml-box" {...props}></Icon>
