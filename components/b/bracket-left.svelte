<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hd36210ot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hd36210ot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:bracket-left" {...props}></Icon>
