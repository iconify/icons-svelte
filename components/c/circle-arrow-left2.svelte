<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yofdfk3ho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yofdfk3ho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:circle-arrow-left2" {...props}></Icon>
