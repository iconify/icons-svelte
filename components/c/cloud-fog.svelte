<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vc2q1fbxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vc2q1fbxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:cloud-fog" {...props}></Icon>
