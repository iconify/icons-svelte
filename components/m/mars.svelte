<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p6xlpdk8s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p6xlpdk8s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:mars" {...props}></Icon>
