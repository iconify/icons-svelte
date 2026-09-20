<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eayb5eiwh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eayb5eiwh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:cloud-sun-hail" {...props}></Icon>
