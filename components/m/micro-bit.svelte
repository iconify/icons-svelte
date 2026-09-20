<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ehcfzl_ej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ehcfzl_ej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:micro-bit" {...props}></Icon>
