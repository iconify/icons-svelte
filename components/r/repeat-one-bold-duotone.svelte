<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bw0ke5bhk.css';
import '../../css/f/f8-fppcwy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bw0ke5bhk"/><path class="f8-fppcwy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:repeat-one-bold-duotone" {...props}></Icon>
