<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o9_1xi4pr.css';
import '../../css/a/anh277ned.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o9_1xi4pr"/><path class="anh277ned"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:conditioner-2-bold-duotone" {...props}></Icon>
