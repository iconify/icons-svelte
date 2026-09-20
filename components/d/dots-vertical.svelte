<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hhv7v7_ld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hhv7v7_ld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:dots-vertical" {...props}></Icon>
