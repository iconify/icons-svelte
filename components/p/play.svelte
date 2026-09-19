<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i0npb9vnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i0npb9vnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="feather:play" {...props}></Icon>
