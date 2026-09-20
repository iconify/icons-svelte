<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0m25c.css';
import '../../css/s/sgi08m.css';
import '../../css/w/wvdtaf.css';
import '../../css/s/so-from-62.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c sgi08m"/><path class="a0m25c wvdtaf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:file-search" {...props}></Icon>
