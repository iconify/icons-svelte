<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wdve8pind.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary wdve8pind"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:badge-duotone" {...props}></Icon>
