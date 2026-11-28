<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zf_i5toqh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zf_i5toqh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:dumbbell" {...props}></Icon>
