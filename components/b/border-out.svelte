<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zd_3jgbwr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zd_3jgbwr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:border-out" {...props}></Icon>
