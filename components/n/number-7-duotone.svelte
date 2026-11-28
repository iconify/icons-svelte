<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iea4ydfqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iea4ydfqj primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:number-7-duotone" {...props}></Icon>
