<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ki73m08oz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ki73m08oz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:inspection-panel-filled" {...props}></Icon>
