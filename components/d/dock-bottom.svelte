<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mssb4p5se.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mssb4p5se"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:dock-bottom" {...props}></Icon>
