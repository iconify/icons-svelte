<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p0tjbtb1u.css';
import '../../css/k/k3m_0ge5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="p0tjbtb1u"/><path class="k3m_0ge5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:password-48" {...props}></Icon>
