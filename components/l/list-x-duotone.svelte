<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lg95o17_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lg95o17_l primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:list-x-duotone" {...props}></Icon>
