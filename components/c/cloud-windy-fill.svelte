<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v9861ybuj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v9861ybuj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:cloud-windy-fill" {...props}></Icon>
