<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i8t1iqbse.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i8t1iqbse primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:bracket-left-duotone" {...props}></Icon>
