<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g1fo9snfu.css';
import '../../css/l/l9cl-boot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="g1fo9snfu"/><path class="l9cl-boot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:peru" {...props}></Icon>
