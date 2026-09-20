<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ksnmxskkl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ksnmxskkl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:face-devil" {...props}></Icon>
