<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/efu3a84qy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="efu3a84qy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:refresh-cw" {...props}></Icon>
