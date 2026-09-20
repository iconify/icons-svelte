<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vf2-xfbed.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vf2-xfbed"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:code" {...props}></Icon>
