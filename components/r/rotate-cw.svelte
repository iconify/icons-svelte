<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hhsf1lb7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hhsf1lb7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:rotate-cw" {...props}></Icon>
