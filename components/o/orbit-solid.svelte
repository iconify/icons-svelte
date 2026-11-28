<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xm1g7_pyc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xm1g7_pyc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:orbit-solid" {...props}></Icon>
