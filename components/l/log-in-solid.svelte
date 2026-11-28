<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/anb2ifbdv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="anb2ifbdv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:log-in-solid" {...props}></Icon>
