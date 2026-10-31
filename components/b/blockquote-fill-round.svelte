<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v_vw0tbqh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v_vw0tbqh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:blockquote-fill-round" {...props}></Icon>
