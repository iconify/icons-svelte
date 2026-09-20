<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yl4dl26nv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yl4dl26nv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:key-square-fill" {...props}></Icon>
