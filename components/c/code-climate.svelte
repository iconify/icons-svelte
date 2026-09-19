<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tfun62owm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tfun62owm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:code-climate" {...props}></Icon>
