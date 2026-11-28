<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e442e8d9k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e442e8d9k primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:number-3-duotone" {...props}></Icon>
