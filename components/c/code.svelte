<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rj10jwbji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rj10jwbji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:code" {...props}></Icon>
