<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xwb2ztm3s.css';
import '../../css/s/sz-8khbph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xwb2ztm3s"/><path class="sz-8khbph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:repo-locked-24" {...props}></Icon>
