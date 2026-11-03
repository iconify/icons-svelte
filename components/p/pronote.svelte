<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/twtj5ebts.css';
import '../../css/y/yg0gmx-wy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="twtj5ebts"/><path class="yg0gmx-wy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pronote" {...props}></Icon>
