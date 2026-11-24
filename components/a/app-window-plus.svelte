<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m0yhc4j3a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m0yhc4j3a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:app-window-plus" {...props}></Icon>
