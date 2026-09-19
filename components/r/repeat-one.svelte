<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kmov_dv6f.css';
import '../../css/x/xzk6xmbpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kmov_dv6f"/><path class="xzk6xmbpp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:repeat-one" {...props}></Icon>
