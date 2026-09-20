<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yrn_u-bfj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yrn_u-bfj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:folder-line-fill" {...props}></Icon>
