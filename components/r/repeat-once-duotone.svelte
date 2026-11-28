<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jd2r3fwxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jd2r3fwxt primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:repeat-once-duotone" {...props}></Icon>
