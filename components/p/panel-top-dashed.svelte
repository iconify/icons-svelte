<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pqufedbiz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pqufedbiz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:panel-top-dashed" {...props}></Icon>
