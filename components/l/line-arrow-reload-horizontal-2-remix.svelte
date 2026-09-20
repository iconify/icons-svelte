<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tntdz1o6j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tntdz1o6j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:line-arrow-reload-horizontal-2-remix" {...props}></Icon>
