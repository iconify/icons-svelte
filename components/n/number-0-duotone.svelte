<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dcu6sacby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dcu6sacby primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:number-0-duotone" {...props}></Icon>
