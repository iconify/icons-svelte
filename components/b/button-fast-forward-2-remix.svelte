<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ctkrq_x0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ctkrq_x0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:button-fast-forward-2-remix" {...props}></Icon>
