<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yia2llbra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yia2llbra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:opennebula" {...props}></Icon>
