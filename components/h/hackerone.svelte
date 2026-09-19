<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bw_wmimbe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bw_wmimbe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:hackerone" {...props}></Icon>
