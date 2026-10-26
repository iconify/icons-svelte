<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ayz9irb2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ayz9irb2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:acupuncture-1" {...props}></Icon>
