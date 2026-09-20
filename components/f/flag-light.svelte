<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xznkh2bjf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xznkh2bjf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:flag-light" {...props}></Icon>
