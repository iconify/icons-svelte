<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yrk6lbcgz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yrk6lbcgz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:page-left-solid" {...props}></Icon>
