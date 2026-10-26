<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yv2yqwsyd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="yv2yqwsyd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:acupuncture-3" {...props}></Icon>
