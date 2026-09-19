<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wq_hm8yes.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wq_hm8yes"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:align-text-top" {...props}></Icon>
