<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m_f6ecczd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m_f6ecczd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-briefcase-outline" {...props}></Icon>
