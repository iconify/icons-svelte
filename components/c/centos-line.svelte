<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e3l3vac6x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e3l3vac6x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:centos-line" {...props}></Icon>
