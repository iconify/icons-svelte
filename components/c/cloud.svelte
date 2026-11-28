<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/selc8tm1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="selc8tm1k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:cloud" {...props}></Icon>
