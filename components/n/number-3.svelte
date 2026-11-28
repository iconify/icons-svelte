<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/niubgw59c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="niubgw59c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:number-3" {...props}></Icon>
