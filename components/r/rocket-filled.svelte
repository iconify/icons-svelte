<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ogx29lbfw.css';
import '../../css/a/azwen8bub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ogx29lbfw"/><path clip-rule="evenodd" class="azwen8bub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:rocket-filled" {...props}></Icon>
