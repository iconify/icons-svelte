<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o8u43xb9m.css';
import '../../css/c/co3iw4m_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o8u43xb9m"/><path class="co3iw4m_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:centos-dark" {...props}></Icon>
