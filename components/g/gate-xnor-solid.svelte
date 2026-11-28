<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yiko28bzq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yiko28bzq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:gate-xnor-solid" {...props}></Icon>
