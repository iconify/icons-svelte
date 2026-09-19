<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/is6skxrui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="is6skxrui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="feather:dollar-sign" {...props}></Icon>
