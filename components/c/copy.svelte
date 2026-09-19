<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v51606bos.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":24};
const content = `<path class="v51606bos"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:copy" {...props}></Icon>
