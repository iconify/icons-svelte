<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gxixch_7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gxixch_7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:backspace-bold" {...props}></Icon>
