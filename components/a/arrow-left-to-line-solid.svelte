<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mc-l_6bjb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mc-l_6bjb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:arrow-left-to-line-solid" {...props}></Icon>
