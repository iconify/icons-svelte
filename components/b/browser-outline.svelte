<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ar30v6f3w.css';
import '../../css/r/ra4bz523e.css';
import '../../css/w/wa0xce7qd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ar30v6f3w"/><circle class="ra4bz523e"/><circle class="wa0xce7qd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:browser-outline" {...props}></Icon>
