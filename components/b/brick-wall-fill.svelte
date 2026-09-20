<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/palu_ab3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="palu_ab3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:brick-wall-fill" {...props}></Icon>
