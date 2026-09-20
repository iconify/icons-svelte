<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t_di7u-yh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t_di7u-yh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:align-text-center-solid" {...props}></Icon>
