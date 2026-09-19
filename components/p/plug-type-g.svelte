<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mmy4nqiui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mmy4nqiui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:plug-type-g" {...props}></Icon>
